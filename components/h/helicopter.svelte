<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doo177jjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="doo177jjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:helicopter" {...props}></Icon>
