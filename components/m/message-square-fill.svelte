<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2n0rlwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw2n0rlwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-fill" {...props}></Icon>
