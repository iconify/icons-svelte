<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyfj05bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyfj05bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:link-broken" {...props}></Icon>
