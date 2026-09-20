<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vss9qgb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vss9qgb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:oil" {...props}></Icon>
