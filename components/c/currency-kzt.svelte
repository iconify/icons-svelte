<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7v7c3b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7v7c3b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-kzt" {...props}></Icon>
