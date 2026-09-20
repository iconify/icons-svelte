<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qae_v0bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qae_v0bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hanger-off" {...props}></Icon>
