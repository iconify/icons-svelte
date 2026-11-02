<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2mko2_4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2mko2_4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:formula-fill" {...props}></Icon>
