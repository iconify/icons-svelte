<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nemrsnj0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nemrsnj0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-question-thin" {...props}></Icon>
