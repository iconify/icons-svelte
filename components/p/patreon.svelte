<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygfhj0bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygfhj0bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:patreon" {...props}></Icon>
