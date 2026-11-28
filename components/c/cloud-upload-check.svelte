<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoxjszbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoxjszbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-upload-check" {...props}></Icon>
