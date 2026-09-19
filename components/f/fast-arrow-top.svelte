<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz7wivbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz7wivbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-top" {...props}></Icon>
