<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6b8s_bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c6b8s_bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fisted-hand-sign" {...props}></Icon>
