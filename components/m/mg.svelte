<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jig-cofsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jig-cofsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mg" {...props}></Icon>
