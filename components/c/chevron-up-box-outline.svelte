<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpmie_b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpmie_b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-up-box-outline" {...props}></Icon>
