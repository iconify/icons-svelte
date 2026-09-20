<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyiwk_buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyiwk_buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-minus-outline" {...props}></Icon>
