<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-qrhb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-qrhb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pythonanywhere" {...props}></Icon>
