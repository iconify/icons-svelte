<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upv6j8a-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upv6j8a-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:fast-forward" {...props}></Icon>
