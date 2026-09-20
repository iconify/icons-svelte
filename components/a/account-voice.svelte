<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmde_brvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmde_brvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-voice" {...props}></Icon>
