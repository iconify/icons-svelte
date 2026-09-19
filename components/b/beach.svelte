<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_s0cc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_s0cc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:beach" {...props}></Icon>
