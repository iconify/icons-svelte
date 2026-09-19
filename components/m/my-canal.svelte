<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rldsltm8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rldsltm8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:my-canal" {...props}></Icon>
