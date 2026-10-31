<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmzrrjbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmzrrjbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-upload-fill-round" {...props}></Icon>
