<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhpnogbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhpnogbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-left" {...props}></Icon>
