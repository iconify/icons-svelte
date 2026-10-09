<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgs6dobqh.css';
import '../../css/o/o1usrlbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rgs6dobqh"/><path class="o1usrlbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pier-20" {...props}></Icon>
