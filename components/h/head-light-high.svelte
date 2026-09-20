<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxpig_jqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxpig_jqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-light-high" {...props}></Icon>
