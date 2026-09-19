<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oajfdu57o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oajfdu57o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lightstrip" {...props}></Icon>
