<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6-sdvapm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/imag2ybny.css';
import '../../css/f/f3_b4ijst.css';
import '../../css/b/bqtd5gbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-sdvapm secondary"/><g class="dt0cm9dhy primary"><path class="imag2ybny"/><path class="f3_b4ijst"/><path class="bqtd5gbgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:archive-duo" {...props}></Icon>
