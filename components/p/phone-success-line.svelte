<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tonk8_bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tonk8_bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-success-line" {...props}></Icon>
