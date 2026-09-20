<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6wn3rbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6wn3rbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astroluma-light" {...props}></Icon>
