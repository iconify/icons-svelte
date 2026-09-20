<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itemg20bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="itemg20bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:blogger" {...props}></Icon>
