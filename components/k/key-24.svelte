<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wov6qjbrb.css';
import '../../css/k/kx5tz624c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wov6qjbrb"/><path class="kx5tz624c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:key-24" {...props}></Icon>
