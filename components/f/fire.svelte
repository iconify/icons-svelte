<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsy1qobdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsy1qobdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fire" {...props}></Icon>
