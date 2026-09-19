<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c0w0gbbmk.css';
import '../../css/i/igivs8afy.css';
import '../../css/b/bjvdyzagy.css';
import '../../css/s/s4ttgicka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c0w0gbbmk"/><path class="igivs8afy"/><path class="bjvdyzagy"/><path class="s4ttgicka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blood-bag" {...props}></Icon>
