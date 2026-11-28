<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaorab1-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaorab1-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coffee-heart" {...props}></Icon>
