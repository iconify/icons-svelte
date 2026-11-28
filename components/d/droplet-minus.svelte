<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8y8kgbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8y8kgbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:droplet-minus" {...props}></Icon>
