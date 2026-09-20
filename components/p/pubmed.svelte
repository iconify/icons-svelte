<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y628m0xwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y628m0xwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pubmed" {...props}></Icon>
