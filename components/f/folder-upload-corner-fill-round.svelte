<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thsueubkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thsueubkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-upload-corner-fill-round" {...props}></Icon>
