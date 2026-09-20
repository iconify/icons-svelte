<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an_xzjbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an_xzjbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:element" {...props}></Icon>
