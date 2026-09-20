<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0m8trbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0m8trbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-3-bold" {...props}></Icon>
