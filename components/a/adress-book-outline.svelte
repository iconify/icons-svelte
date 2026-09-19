<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7x4gveff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7x4gveff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:adress-book-outline" {...props}></Icon>
