<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dil75-s_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dil75-s_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:edit2-filled" {...props}></Icon>
