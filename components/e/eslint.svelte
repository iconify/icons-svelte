<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fipcg1rcz.css';
import '../../css/g/gtk4lacos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fipcg1rcz"/><path class="gtk4lacos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:eslint" {...props}></Icon>
