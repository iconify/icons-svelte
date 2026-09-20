<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqs2jsb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqs2jsb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:directions" {...props}></Icon>
