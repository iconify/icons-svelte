<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua6aqkoxj.css';
import '../../css/d/d4zi-lbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua6aqkoxj"/><path class="d4zi-lbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-bold-duotone" {...props}></Icon>
