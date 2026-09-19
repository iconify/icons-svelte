<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-jvs6u8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-jvs6u8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-up-outline" {...props}></Icon>
