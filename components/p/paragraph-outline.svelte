<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk-zs26ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-zs26ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:paragraph-outline" {...props}></Icon>
