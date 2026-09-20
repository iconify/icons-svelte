<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ljxq3-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ljxq3-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anta" {...props}></Icon>
