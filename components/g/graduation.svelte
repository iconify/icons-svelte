<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtvcw1bvs.css';
import '../../css/f/f5u8_gz6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvcw1bvs"/><path class="f5u8_gz6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:graduation" {...props}></Icon>
