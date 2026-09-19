<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-fr6cczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-fr6cczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:plus-solid" {...props}></Icon>
