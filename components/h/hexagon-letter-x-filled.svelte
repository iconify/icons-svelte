<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqfzzh-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqfzzh-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-x-filled" {...props}></Icon>
