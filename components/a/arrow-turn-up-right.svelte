<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvs4msbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvs4msbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-turn-up-right" {...props}></Icon>
