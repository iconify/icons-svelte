<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i4c7z3ber.css';
import '../../css/g/gyo3mhbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lamp-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="i4c7z3ber"/><path class="gyo3mhbbj"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:lamp-outline" {...props}></Icon>
