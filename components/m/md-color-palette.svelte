<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5vxb6zvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5vxb6zvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-color-palette" {...props}></Icon>
