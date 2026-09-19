<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x47blvbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x47blvbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fluffy-cloud" {...props}></Icon>
