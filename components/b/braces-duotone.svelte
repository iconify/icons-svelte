<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1j71ccor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1j71ccor primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:braces-duotone" {...props}></Icon>
