<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kikva3tqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kikva3tqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:filter-remove" {...props}></Icon>
