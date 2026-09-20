<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f61c29bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f61c29bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:horseshoe" {...props}></Icon>
