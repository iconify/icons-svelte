<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdfbt-bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdfbt-bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:check-duotone" {...props}></Icon>
