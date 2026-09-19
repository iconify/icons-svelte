<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ravrl3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t4ravrl3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:dim-button" {...props}></Icon>
