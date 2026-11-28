<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeg7z84hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeg7z84hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:juice-box" {...props}></Icon>
