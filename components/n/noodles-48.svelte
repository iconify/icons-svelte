<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_kyy_bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b_kyy_bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noodles-48" {...props}></Icon>
