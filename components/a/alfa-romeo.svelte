<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7h1q6bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7h1q6bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:alfa-romeo" {...props}></Icon>
