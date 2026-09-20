<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezs_2ymoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezs_2ymoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pizza-slice" {...props}></Icon>
