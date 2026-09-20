<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcc4oqbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcc4oqbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-right2" {...props}></Icon>
