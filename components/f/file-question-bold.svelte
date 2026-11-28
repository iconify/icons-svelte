<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq6o97y7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nq6o97y7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-question-bold" {...props}></Icon>
