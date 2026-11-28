<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvs0yibzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvs0yibzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bus" {...props}></Icon>
