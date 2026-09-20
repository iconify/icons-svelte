<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nln9_m3-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nln9_m3-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:guitar-pick-filled" {...props}></Icon>
