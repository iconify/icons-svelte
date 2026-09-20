<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp_plwb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kp_plwb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-down-outline" {...props}></Icon>
