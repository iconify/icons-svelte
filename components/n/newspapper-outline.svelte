<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1t5l6sww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1t5l6sww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:newspapper-outline" {...props}></Icon>
