<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwikjcbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwikjcbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-double-right-solid" {...props}></Icon>
