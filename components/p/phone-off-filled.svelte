<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfq_mub-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfq_mub-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-off-filled" {...props}></Icon>
