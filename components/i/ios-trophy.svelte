<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irfpfd56o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irfpfd56o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-trophy" {...props}></Icon>
