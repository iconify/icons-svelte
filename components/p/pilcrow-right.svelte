<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvo9sobje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvo9sobje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pilcrow-right" {...props}></Icon>
