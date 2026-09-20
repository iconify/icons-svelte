<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do7ha-bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do7ha-bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nodedotjs" {...props}></Icon>
