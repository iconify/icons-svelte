<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc4nkls7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4nkls7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-dollar-sign-solid" {...props}></Icon>
