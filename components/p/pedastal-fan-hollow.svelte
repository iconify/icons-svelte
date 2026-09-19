<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt807ulwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt807ulwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pedastal-fan-hollow" {...props}></Icon>
