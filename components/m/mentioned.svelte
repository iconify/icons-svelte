<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5ornubpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ornubpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mentioned" {...props}></Icon>
