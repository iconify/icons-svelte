<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oflcx7bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oflcx7bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-receive-01" {...props}></Icon>
