<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahotrmbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahotrmbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:align-justify-outline" {...props}></Icon>
