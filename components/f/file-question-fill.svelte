<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltq6thbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ltq6thbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-question-fill" {...props}></Icon>
