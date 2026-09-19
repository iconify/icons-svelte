<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql8ix6b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ql8ix6b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-cross-square" {...props}></Icon>
