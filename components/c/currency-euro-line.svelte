<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfw07lh_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfw07lh_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-euro-line" {...props}></Icon>
