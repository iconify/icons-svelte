<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imx95tuqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imx95tuqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:octanerender" {...props}></Icon>
