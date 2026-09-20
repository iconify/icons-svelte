<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2s2km0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud2s2km0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-horizontal" {...props}></Icon>
