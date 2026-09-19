<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dso2jklbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dso2jklbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-down" {...props}></Icon>
