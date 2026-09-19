<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_j688pvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_j688pvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-off-solid" {...props}></Icon>
