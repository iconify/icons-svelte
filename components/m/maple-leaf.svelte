<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd7sdd_nh.css';
import '../../css/v/v8fd06b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qd7sdd_nh"/><path class="v8fd06b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:maple-leaf" {...props}></Icon>
