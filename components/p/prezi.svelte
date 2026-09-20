<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdfx-4bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfx-4bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prezi" {...props}></Icon>
