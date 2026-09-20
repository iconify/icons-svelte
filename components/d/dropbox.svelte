<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe81t3jjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe81t3jjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dropbox" {...props}></Icon>
