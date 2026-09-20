<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2lg_hbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2lg_hbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-remove" {...props}></Icon>
