<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oao_97big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oao_97big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pillar-spot-3" {...props}></Icon>
