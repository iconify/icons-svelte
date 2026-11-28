<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iazjm4e3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iazjm4e3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cow" {...props}></Icon>
