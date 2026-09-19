<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj__wgbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj__wgbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:folder" {...props}></Icon>
