<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk_r9ibjr.css';
import '../../css/v/vj58-bbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jk_r9ibjr"/><path class="vj58-bbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-upload-outline" {...props}></Icon>
