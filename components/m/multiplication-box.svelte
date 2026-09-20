<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7fu1b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7fu1b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:multiplication-box" {...props}></Icon>
