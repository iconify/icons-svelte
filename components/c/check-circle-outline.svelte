<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffhs73-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffhs73-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:check-circle-outline" {...props}></Icon>
