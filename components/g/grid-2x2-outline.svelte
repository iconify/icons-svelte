<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hulqqcxho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hulqqcxho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-outline" {...props}></Icon>
