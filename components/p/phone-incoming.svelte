<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkbp6n8mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkbp6n8mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:phone-incoming" {...props}></Icon>
