<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7b8kgbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7b8kgbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-left-large-bulk-round" {...props}></Icon>
