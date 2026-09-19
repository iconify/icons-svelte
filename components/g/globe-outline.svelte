<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znezuzb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znezuzb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:globe-outline" {...props}></Icon>
