<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0gre_j9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0gre_j9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cat" {...props}></Icon>
