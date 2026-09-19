<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt06asixu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt06asixu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-right-up" {...props}></Icon>
