<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d938krbry.css';
import '../../css/e/eid02wl-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d938krbry"/><path class="eid02wl-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crop-20" {...props}></Icon>
