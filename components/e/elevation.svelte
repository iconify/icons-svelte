<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj4ed5nrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4ed5nrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:elevation" {...props}></Icon>
