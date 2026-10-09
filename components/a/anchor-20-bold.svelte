<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg0v5rbgp.css';
import '../../css/w/wj1xj8bpq.css';
import '../../css/l/lu2e92trj.css';
import '../../css/b/b-sd-zboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vg0v5rbgp"/><path class="wj1xj8bpq"/><path class="lu2e92trj"/><path class="b-sd-zboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anchor-20-bold" {...props}></Icon>
