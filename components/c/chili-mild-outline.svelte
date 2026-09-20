<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u899l7b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u899l7b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chili-mild-outline" {...props}></Icon>
