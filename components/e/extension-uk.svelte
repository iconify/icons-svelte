<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9aimcb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9aimcb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:extension-uk" {...props}></Icon>
