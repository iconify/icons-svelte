<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp5b8z1rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp5b8z1rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:giggle-filled" {...props}></Icon>
