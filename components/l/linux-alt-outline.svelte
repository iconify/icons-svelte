<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxim2_bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qxim2_bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:linux-alt-outline" {...props}></Icon>
