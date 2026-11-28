<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_yl57rvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_yl57rvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-star" {...props}></Icon>
