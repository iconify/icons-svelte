<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyxh2xy5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyxh2xy5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-saw" {...props}></Icon>
