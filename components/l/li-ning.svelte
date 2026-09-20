<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcho2thtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcho2thtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:li-ning" {...props}></Icon>
