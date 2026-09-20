<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ias0wlihu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ias0wlihu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-outline" {...props}></Icon>
