<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f200fw0ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f200fw0ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:noun-project" {...props}></Icon>
