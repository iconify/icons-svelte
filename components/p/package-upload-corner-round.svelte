<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc1h1wbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc1h1wbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-upload-corner-round" {...props}></Icon>
