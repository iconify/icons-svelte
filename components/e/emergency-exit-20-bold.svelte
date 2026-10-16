<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5tyujbpm.css';
import '../../css/l/l3tq00bvz.css';
import '../../css/d/dce81qbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d5tyujbpm"/><path class="l3tq00bvz"/><path class="dce81qbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emergency-exit-20-bold" {...props}></Icon>
