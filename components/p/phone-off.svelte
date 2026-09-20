<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo60o6k2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo60o6k2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:phone-off" {...props}></Icon>
