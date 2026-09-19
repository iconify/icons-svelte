<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9xz_0btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9xz_0btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-pet-feeder-c1" {...props}></Icon>
