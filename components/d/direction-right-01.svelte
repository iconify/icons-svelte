<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joaz6-u6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joaz6-u6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:direction-right-01" {...props}></Icon>
