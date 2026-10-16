<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9i0psc1u.css';
import '../../css/d/d58o7tbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m9i0psc1u"/><path class="d58o7tbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-transformer-20" {...props}></Icon>
