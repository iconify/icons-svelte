<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu80dudss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu80dudss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-1-1" {...props}></Icon>
