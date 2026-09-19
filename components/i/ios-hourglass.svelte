<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q84q2v45v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q84q2v45v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-hourglass" {...props}></Icon>
