<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avd8sacsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avd8sacsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-euro-2-line" {...props}></Icon>
