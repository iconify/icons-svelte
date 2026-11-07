<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_gtob6t.css';
import '../../css/b/bz0qnvbjd.css';
import '../../css/z/zoz5x5bue.css';
import '../../css/i/io_i03bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="bz0qnvbjd"/><path class="zoz5x5bue"/><path clip-rule="evenodd" class="io_i03bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-library-2-bold" {...props}></Icon>
