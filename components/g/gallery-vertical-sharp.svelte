<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-dnl_yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie-dnl_yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-sharp" {...props}></Icon>
