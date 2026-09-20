<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkxsbabrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkxsbabrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pix-fill" {...props}></Icon>
