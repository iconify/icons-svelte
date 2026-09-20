<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdzp0ta_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdzp0ta_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cone-off" {...props}></Icon>
