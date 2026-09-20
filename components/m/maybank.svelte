<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj_2p5drs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1568};
const content = `<path class="bj_2p5drs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:maybank" {...props}></Icon>
