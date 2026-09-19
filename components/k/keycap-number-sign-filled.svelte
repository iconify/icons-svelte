<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndu34km1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ndu34km1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-number-sign-filled" {...props}></Icon>
