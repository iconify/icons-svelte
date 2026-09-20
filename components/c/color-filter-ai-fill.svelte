<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa2wmjajw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa2wmjajw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:color-filter-ai-fill" {...props}></Icon>
