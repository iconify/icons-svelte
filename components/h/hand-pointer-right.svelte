<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7cvs3lqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cvs3lqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-right" {...props}></Icon>
