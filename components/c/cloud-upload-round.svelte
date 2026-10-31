<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y15k2bb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y15k2bb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-upload-round" {...props}></Icon>
