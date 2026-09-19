<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kul0447wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kul0447wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-none" {...props}></Icon>
