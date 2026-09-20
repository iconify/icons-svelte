<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy3vt9bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy3vt9bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heart-off-sharp" {...props}></Icon>
