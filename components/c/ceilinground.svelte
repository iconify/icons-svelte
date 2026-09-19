<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1db3edod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1db3edod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceilinground" {...props}></Icon>
