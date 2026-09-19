<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gix6z2bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gix6z2bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bedroom-alt-numbered" {...props}></Icon>
