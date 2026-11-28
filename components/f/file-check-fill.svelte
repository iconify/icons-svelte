<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4tu03bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u4tu03bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-check-fill" {...props}></Icon>
