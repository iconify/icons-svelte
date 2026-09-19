<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv3rhpbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv3rhpbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:minimize-01" {...props}></Icon>
