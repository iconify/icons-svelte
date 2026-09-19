<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-o-z-nbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-o-z-nbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:renault-invert" {...props}></Icon>
