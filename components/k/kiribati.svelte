<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5yjr_spk.css';
import '../../css/p/p075md36j.css';
import '../../css/l/ldzer7b8d.css';
import '../../css/h/hz4bs5lpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="q5yjr_spk"/><path class="p075md36j"/><path class="ldzer7b8d"/><path class="hz4bs5lpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:kiribati" {...props}></Icon>
