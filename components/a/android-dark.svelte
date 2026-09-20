<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwsejm1ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwsejm1ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-dark" {...props}></Icon>
