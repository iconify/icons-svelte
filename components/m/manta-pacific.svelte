<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_g2vzb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_g2vzb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:manta-pacific" {...props}></Icon>
