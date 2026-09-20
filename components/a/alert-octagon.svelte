<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_4kpbots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_4kpbots"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-octagon" {...props}></Icon>
