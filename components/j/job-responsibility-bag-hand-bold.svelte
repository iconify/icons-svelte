<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmd_g055q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmd_g055q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:job-responsibility-bag-hand-bold" {...props}></Icon>
