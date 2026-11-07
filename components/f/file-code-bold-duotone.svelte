<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd8bzbml.css';
import '../../css/w/wa67eqk3b.css';
import '../../css/l/lqdbwbc4f.css';
import '../../css/r/r-s7r2hkm.css';
import '../../css/k/kn13bqbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="wa67eqk3b"/><path class="lqdbwbc4f"/><path class="r-s7r2hkm"/><path class="kn13bqbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-code-bold-duotone" {...props}></Icon>
