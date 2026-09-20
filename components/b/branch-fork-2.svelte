<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur2c4ccsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur2c4ccsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:branch-fork-2" {...props}></Icon>
