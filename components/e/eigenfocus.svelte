<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0y__vby.css';
import '../../css/m/mpdhyabli.css';
import '../../css/o/o5sq00_9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lx0y__vby"/><path class="mpdhyabli"/><path class="o5sq00_9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eigenfocus" {...props}></Icon>
