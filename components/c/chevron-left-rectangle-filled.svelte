<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zez2vnb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zez2vnb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-left-rectangle-filled" {...props}></Icon>
