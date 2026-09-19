<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myq2e5yds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="myq2e5yds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-network" {...props}></Icon>
