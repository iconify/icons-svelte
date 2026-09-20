<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urr3lhbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urr3lhbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-close-fill" {...props}></Icon>
