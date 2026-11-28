<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v29kbzb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v29kbzb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bring-forward-light" {...props}></Icon>
