<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2d394ajk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2d394ajk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cash-register-outline" {...props}></Icon>
