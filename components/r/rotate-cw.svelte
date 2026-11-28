<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8af2zbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8af2zbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rotate-cw" {...props}></Icon>
