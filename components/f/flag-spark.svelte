<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymjt_ev0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymjt_ev0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-spark" {...props}></Icon>
