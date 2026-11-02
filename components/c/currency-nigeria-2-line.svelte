<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p85rznbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p85rznbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-nigeria-2-line" {...props}></Icon>
