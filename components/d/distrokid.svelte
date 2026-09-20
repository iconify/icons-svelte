<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6y2_o5nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6y2_o5nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:distrokid" {...props}></Icon>
