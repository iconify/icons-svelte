<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_md2sb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_md2sb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:mobile-phone-outline" {...props}></Icon>
