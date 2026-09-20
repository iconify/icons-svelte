<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1g_hup3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1g_hup3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:helium" {...props}></Icon>
