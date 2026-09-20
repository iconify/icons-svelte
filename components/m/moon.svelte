<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw6y84_8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw6y84_8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:moon" {...props}></Icon>
