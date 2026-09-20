<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkivbwxmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lkivbwxmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:report" {...props}></Icon>
