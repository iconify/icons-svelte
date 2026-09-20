<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wixg6xxac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wixg6xxac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:haiper" {...props}></Icon>
