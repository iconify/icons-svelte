<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkq57kf6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="hkq57kf6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dice-d20" {...props}></Icon>
