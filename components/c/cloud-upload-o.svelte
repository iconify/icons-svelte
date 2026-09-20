<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs3uvlr_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs3uvlr_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:cloud-upload-o" {...props}></Icon>
