<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frspmqwww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="frspmqwww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:primitive-dot" {...props}></Icon>
