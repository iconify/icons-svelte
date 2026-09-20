<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onn7hn6ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onn7hn6ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kahoot" {...props}></Icon>
