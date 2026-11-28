<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5tfqb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di5tfqb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:grid-plus" {...props}></Icon>
