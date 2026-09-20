<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbccqd-dr.css';
import '../../css/y/y_4cj2byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbccqd-dr"/><path class="y_4cj2byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:print-text-bold" {...props}></Icon>
