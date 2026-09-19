<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgdlmx9qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdlmx9qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-right" {...props}></Icon>
