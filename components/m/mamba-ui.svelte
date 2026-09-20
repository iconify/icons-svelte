<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1yvqhbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1yvqhbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mamba-ui" {...props}></Icon>
