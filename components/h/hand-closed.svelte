<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3d8ef5th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3d8ef5th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-closed" {...props}></Icon>
