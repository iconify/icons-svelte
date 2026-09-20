<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ihiqo8l.css';
import '../../css/f/fbuv3ib1d.css';
import '../../css/i/i81jb4lpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ihiqo8l"/><path class="fbuv3ib1d"/><path class="i81jb4lpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:prime" {...props}></Icon>
