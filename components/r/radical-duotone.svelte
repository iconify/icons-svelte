<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubpmymb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubpmymb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:radical-duotone" {...props}></Icon>
