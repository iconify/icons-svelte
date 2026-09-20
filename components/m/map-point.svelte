<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzy4r-3vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzy4r-3vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-point" {...props}></Icon>
