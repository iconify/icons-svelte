<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmc06hb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmc06hb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:newspaper-outline" {...props}></Icon>
