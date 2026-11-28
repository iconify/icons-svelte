<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvxuy3bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvxuy3bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-graph-solid" {...props}></Icon>
