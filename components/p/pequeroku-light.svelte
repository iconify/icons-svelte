<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9lccb89g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9lccb89g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pequeroku-light" {...props}></Icon>
