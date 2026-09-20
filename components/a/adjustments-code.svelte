<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz1d02xod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz1d02xod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-code" {...props}></Icon>
