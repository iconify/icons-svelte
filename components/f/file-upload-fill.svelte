<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq5o52bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq5o52bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-upload-fill" {...props}></Icon>
