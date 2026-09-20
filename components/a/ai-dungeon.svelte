<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh_4fdb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh_4fdb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ai-dungeon" {...props}></Icon>
