<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4r004bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e4r004bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-star-filled" {...props}></Icon>
