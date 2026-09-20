<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hscdczsec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hscdczsec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-check-outline" {...props}></Icon>
