<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vva995_fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-1};
const content = `<path class="vva995_fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:highlighter" {...props}></Icon>
