<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj6j6-bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj6j6-bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eye-off-sharp" {...props}></Icon>
