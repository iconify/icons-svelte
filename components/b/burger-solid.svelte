<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzh5yui8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzh5yui8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:burger-solid" {...props}></Icon>
