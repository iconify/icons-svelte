<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dywh2-b_s.css';
import '../../css/q/qqyc4mb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dywh2-b_s"/><path class="qqyc4mb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopile-20-bold" {...props}></Icon>
