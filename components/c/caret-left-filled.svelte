<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z60422b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z60422b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:caret-left-filled" {...props}></Icon>
