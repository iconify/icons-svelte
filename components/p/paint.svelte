<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfe9l6bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfe9l6bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:paint" {...props}></Icon>
