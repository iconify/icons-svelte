<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_fbkkbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_fbkkbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-area" {...props}></Icon>
