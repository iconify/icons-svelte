<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv9o7hb4h.css';
import '../../css/b/bpl-meb0s.css';
import '../../css/i/ic--wlbit.css';
import '../../css/p/pmf4o37fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv9o7hb4h"/><path class="bpl-meb0s"/><path class="ic--wlbit"/><path class="pmf4o37fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bicycle" {...props}></Icon>
