<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bigfy4btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bigfy4btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gumroad-line" {...props}></Icon>
