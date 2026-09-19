<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg-bs7b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-bs7b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:bold" {...props}></Icon>
