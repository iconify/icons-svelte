<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdqopwbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":0.1,"top":0.1};
const content = `<path class="hdqopwbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:droplet-outline" {...props}></Icon>
