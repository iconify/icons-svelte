<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htib2p0us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htib2p0us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:phi" {...props}></Icon>
