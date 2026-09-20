<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bum_u10rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bum_u10rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ear-line" {...props}></Icon>
