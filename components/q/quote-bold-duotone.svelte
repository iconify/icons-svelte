<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk6ovimpe.css';
import '../../css/g/g9tggne-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk6ovimpe"/><path class="g9tggne-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quote-bold-duotone" {...props}></Icon>
