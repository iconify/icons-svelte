<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ban172hde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ban172hde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:path-square-filled" {...props}></Icon>
