<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blju_tb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="blju_tb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:intersex" {...props}></Icon>
