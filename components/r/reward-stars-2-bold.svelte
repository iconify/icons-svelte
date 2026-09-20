<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4sznb5jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4sznb5jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:reward-stars-2-bold" {...props}></Icon>
