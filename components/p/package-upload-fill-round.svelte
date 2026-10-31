<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbxmv9bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxmv9bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-upload-fill-round" {...props}></Icon>
