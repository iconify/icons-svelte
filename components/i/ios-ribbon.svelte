<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-s_g5rvf.css';
import '../../css/s/sfb9xk9fs.css';
import '../../css/o/ob232qb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-s_g5rvf"/><path class="sfb9xk9fs"/><path class="ob232qb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-ribbon" {...props}></Icon>
