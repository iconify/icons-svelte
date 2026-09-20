<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7i1ukt-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7i1ukt-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:airbnb" {...props}></Icon>
