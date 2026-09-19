<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj81u2bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jj81u2bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:battery" {...props}></Icon>
