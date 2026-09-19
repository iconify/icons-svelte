<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0dd72brq.css';
import '../../css/v/v1z4zvbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dd72brq"/><path class="v1z4zvbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calculator" {...props}></Icon>
