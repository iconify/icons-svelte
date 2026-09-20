<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fls6n_bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fls6n_bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mdx" {...props}></Icon>
