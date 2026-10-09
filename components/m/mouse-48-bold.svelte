<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cau1vhb9o.css';
import '../../css/l/lm7opbs2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cau1vhb9o"/><path class="lm7opbs2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mouse-48-bold" {...props}></Icon>
