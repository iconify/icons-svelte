<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n11sem1pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="n11sem1pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-code" {...props}></Icon>
