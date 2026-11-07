<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_gtob6t.css';
import '../../css/b/bz0qnvbjd.css';
import '../../css/f/f_w5wdbfk.css';
import '../../css/b/bwm8hf_io.css';
import '../../css/r/r6zg66thw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="bz0qnvbjd"/><path clip-rule="evenodd" class="f_w5wdbfk"/><path class="bwm8hf_io"/><path class="r6zg66thw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-library-bold" {...props}></Icon>
