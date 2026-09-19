<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh3vw1bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lh3vw1bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:laraveljetstream-wordmark" {...props}></Icon>
