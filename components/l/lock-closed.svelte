<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8wvaibzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8wvaibzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:lock-closed" {...props}></Icon>
