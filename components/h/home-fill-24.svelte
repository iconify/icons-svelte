<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7-q23bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7-q23bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:home-fill-24" {...props}></Icon>
