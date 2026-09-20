<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8byqac1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8byqac1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:chevron-double-down" {...props}></Icon>
