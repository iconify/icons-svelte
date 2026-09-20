<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stcw4r39t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stcw4r39t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:blx" {...props}></Icon>
