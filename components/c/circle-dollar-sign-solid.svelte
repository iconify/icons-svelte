<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwamgkbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwamgkbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dollar-sign-solid" {...props}></Icon>
