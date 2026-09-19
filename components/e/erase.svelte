<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czgsjqbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czgsjqbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:erase" {...props}></Icon>
