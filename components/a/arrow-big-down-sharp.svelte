<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk0lrcc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk0lrcc_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-down-sharp" {...props}></Icon>
