<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r89p1bbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r89p1bbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:left-indent-alt" {...props}></Icon>
