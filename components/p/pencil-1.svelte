<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu4rbsbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu4rbsbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pencil-1" {...props}></Icon>
