<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe170yvls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe170yvls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:orchardcore" {...props}></Icon>
