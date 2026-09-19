<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjqhxbbwg.css';
import '../../css/g/g6xizdbtb.css';
import '../../css/o/o15x4kbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjqhxbbwg"/><path class="g6xizdbtb"/><path class="o15x4kbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:assistive-listening-system" {...props}></Icon>
