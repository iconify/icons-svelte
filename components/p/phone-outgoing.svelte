<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz6v6hiby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz6v6hiby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:phone-outgoing" {...props}></Icon>
