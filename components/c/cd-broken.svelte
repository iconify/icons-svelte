<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3k4x7c1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3k4x7c1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cd-broken" {...props}></Icon>
