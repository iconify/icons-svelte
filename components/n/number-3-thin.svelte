<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duwfcvz3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duwfcvz3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-thin" {...props}></Icon>
