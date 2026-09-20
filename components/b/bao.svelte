<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyu-xlb4c.css';
import '../../css/m/m1ot_8bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyu-xlb4c"/><path clip-rule="evenodd" class="m1ot_8bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bao" {...props}></Icon>
