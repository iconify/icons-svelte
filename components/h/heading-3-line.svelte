<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc_nmlokk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_nmlokk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-3-line" {...props}></Icon>
