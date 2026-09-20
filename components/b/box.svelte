<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2fa8bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz2fa8bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:box" {...props}></Icon>
