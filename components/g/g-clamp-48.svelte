<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxqv9lhyv.css';
import '../../css/c/cg6w78bdt.css';
import '../../css/z/zr4agjfqn.css';
import '../../css/s/svkr3ie9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qxqv9lhyv"/><path class="cg6w78bdt"/><path class="zr4agjfqn"/><path class="svkr3ie9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:g-clamp-48" {...props}></Icon>
