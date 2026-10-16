<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8833_-nr.css';
import '../../css/g/gwws77byj.css';
import '../../css/h/hjobm6b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q8833_-nr"/><path class="gwws77byj"/><path class="hjobm6b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-pitch-20" {...props}></Icon>
