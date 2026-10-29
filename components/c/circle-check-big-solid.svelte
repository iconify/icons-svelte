<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldcxc-d2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldcxc-d2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-check-big-solid" {...props}></Icon>
