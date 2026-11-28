<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dih7k4bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dih7k4bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:briefcase-search" {...props}></Icon>
