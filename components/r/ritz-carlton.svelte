<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghapr57hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghapr57hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ritz-carlton" {...props}></Icon>
