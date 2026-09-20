<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdxt6vsyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdxt6vsyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:airplane-mode-bold" {...props}></Icon>
