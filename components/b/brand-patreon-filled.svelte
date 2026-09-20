<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4fgg8b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4fgg8b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-patreon-filled" {...props}></Icon>
