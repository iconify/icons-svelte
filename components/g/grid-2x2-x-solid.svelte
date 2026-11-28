<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjyisn2gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjyisn2gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-2x2-x-solid" {...props}></Icon>
