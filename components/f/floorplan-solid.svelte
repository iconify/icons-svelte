<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v71yyxbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="v71yyxbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:floorplan-solid" {...props}></Icon>
