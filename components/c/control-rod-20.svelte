<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq_n0i1md.css';
import '../../css/h/hjm-ymvbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qq_n0i1md"/><path class="hjm-ymvbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-rod-20" {...props}></Icon>
