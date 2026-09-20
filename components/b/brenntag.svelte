<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_jpmb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4_jpmb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:brenntag" {...props}></Icon>
