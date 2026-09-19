<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_pl-mkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="we_pl-mkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:n8n" {...props}></Icon>
