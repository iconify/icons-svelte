<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h66rubb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="h66rubb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hangout" {...props}></Icon>
