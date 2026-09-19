<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvxm3_bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxm3_bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:firetv" {...props}></Icon>
