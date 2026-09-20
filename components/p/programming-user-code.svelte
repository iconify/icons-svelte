<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl11knbwz.css';
import '../../css/m/m2ikeob3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl11knbwz"/><path class="m2ikeob3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:programming-user-code" {...props}></Icon>
