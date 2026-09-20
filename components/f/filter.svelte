<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3svh-r8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3svh-r8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:filter" {...props}></Icon>
