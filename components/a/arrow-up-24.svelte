<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgsioskge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgsioskge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-24" {...props}></Icon>
