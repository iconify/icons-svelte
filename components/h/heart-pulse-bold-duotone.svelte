<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_innbce.css';
import '../../css/k/khl7ijbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_innbce"/><path class="khl7ijbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-pulse-bold-duotone" {...props}></Icon>
