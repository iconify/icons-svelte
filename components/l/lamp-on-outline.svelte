<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i4c7z3ber.css';
import '../../css/g/gyo3mhbbj.css';
import '../../css/w/wqyu5woqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lamp-on-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="i4c7z3ber"/><path class="gyo3mhbbj"/><path clip-rule="evenodd" class="wqyu5woqd"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:lamp-on-outline" {...props}></Icon>
