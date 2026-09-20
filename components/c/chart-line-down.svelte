<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9zk82b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9zk82b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-down" {...props}></Icon>
