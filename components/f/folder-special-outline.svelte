<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl-3rkfbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl-3rkfbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-special-outline" {...props}></Icon>
