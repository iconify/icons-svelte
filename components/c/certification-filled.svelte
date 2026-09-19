<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx7lam2sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx7lam2sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:certification-filled" {...props}></Icon>
