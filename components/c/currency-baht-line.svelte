<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaxm8-_2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaxm8-_2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-baht-line" {...props}></Icon>
