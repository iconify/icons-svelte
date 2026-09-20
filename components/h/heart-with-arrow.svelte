<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm4miebwu.css';
import '../../css/k/kbtpf3fuc.css';
import '../../css/g/gcdi2ob1m.css';
import '../../css/o/oaxr94b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zm4miebwu"/><path class="kbtpf3fuc"/><path class="gcdi2ob1m"/><path class="oaxr94b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heart-with-arrow" {...props}></Icon>
