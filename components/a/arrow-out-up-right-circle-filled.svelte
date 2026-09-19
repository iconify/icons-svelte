<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_38ooa_j.css';
import '../../css/h/h2egwczhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_38ooa_j"/><path class="h2egwczhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-circle-filled" {...props}></Icon>
