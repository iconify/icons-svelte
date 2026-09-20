<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zila6obrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zila6obrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:microphone-1-bold" {...props}></Icon>
