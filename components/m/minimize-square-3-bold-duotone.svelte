<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/a/a50m54bhh.css';
import '../../css/r/rln165b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="a50m54bhh"/><path class="rln165b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-3-bold-duotone" {...props}></Icon>
