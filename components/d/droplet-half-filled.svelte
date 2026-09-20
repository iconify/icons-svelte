<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb56hqbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb56hqbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-half-filled" {...props}></Icon>
