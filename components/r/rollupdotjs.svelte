<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it7lnachd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it7lnachd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rollupdotjs" {...props}></Icon>
