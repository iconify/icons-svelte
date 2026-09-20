<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd-wilcdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd-wilcdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-open" {...props}></Icon>
