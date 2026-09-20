<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfivwjbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfivwjbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:neo4j" {...props}></Icon>
