<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/objhju3au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="objhju3au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cbc" {...props}></Icon>
