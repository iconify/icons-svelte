<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmo5pdb9h.css';
import '../../css/p/p5fk5_2cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kmo5pdb9h"/><path class="p5fk5_2cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:highlighter-20" {...props}></Icon>
