<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjib77b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjib77b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-x" {...props}></Icon>
