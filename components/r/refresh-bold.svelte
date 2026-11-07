<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdf92f1xn.css';
import '../../css/b/b3iiu6hfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdf92f1xn"/><path class="b3iiu6hfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-bold" {...props}></Icon>
