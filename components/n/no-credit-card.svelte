<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si2_iqbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si2_iqbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:no-credit-card" {...props}></Icon>
