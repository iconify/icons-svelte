<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jigebqbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jigebqbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chevrons-down" {...props}></Icon>
