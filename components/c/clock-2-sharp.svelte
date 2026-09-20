<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgnm92b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgnm92b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-2-sharp" {...props}></Icon>
