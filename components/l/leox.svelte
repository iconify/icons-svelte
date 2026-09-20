<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjkiu1vyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjkiu1vyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:leox" {...props}></Icon>
