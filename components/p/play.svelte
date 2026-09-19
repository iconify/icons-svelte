<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qexnws2ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qexnws2ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:play" {...props}></Icon>
