<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oia2jebxk.css';
import '../../css/e/emuklcgdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="oia2jebxk"/><path class="emuklcgdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-horizontal-filled" {...props}></Icon>
