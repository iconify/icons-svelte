<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-t_xccjl.css';
import '../../css/o/o2jt7mbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y-t_xccjl"/><path class="o2jt7mbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:phone-incoming-call" {...props}></Icon>
