<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd2umnbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2umnbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fuel" {...props}></Icon>
