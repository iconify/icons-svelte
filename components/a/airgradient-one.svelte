<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc3tj3bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc3tj3bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:airgradient-one" {...props}></Icon>
