<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3k-7ccja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3k-7ccja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-clock" {...props}></Icon>
