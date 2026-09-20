<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seiyok0se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seiyok0se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lucid" {...props}></Icon>
