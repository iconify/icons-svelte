<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs0_gzboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs0_gzboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:canine" {...props}></Icon>
