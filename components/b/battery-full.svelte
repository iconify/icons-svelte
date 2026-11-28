<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pitxv8bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pitxv8bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:battery-full" {...props}></Icon>
