<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/god23jbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="god23jbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-down-double" {...props}></Icon>
