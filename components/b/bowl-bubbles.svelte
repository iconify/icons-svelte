<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr-hoeb6g.css';
import '../../css/u/u8hb6sbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b zr-hoeb6g"/><path class="b u8hb6sbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-bubbles" {...props}></Icon>
