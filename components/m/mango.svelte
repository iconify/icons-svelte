<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahi8a0pqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahi8a0pqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:mango" {...props}></Icon>
