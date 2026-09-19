<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvc0dx3lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvc0dx3lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-up-left" {...props}></Icon>
