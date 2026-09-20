<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdpq3-2hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdpq3-2hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jpeg" {...props}></Icon>
