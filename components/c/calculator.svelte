<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwceodwry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwceodwry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:calculator" {...props}></Icon>
