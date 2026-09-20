<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-s44ccsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-s44ccsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:navigate-fill" {...props}></Icon>
