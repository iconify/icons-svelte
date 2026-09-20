<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fde5jabaf.css';
import '../../css/k/k4nhvymim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fde5jabaf"/><path class="k4nhvymim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:accounting-coins-bold" {...props}></Icon>
