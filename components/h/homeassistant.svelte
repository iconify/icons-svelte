<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q84-m7bmy.css';
import '../../css/z/zr8ct4-nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q84-m7bmy"/><path class="zr8ct4-nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:homeassistant" {...props}></Icon>
