<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bog__x_pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bog__x_pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:baseline" {...props}></Icon>
