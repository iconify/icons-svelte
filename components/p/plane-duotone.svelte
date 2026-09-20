<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqt-fc2_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqt-fc2_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-duotone" {...props}></Icon>
