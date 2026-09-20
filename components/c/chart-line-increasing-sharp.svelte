<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdov0ybnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdov0ybnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-increasing-sharp" {...props}></Icon>
