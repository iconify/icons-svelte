<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly2d8dboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly2d8dboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-double-up" {...props}></Icon>
