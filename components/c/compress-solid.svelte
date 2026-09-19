<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov-d0q17d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov-d0q17d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:compress-solid" {...props}></Icon>
