<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg2mv0bwm.css';
import '../../css/x/x9xdhqbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg2mv0bwm"/><path class="x9xdhqbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-10-filled" {...props}></Icon>
