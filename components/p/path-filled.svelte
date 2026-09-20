<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az8eyjsjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az8eyjsjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:path-filled" {...props}></Icon>
