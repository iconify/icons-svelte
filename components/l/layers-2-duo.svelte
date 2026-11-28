<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fffsaibbs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o49n02bnz.css';
import '../../css/a/agi7abb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fffsaibbs secondary"/><g class="dt0cm9dhy primary"><path class="o49n02bnz"/><path class="agi7abb2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-2-duo" {...props}></Icon>
