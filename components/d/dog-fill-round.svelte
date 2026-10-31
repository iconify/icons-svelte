<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1u3wbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo1u3wbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dog-fill-round" {...props}></Icon>
