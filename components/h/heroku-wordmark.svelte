<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx6l2l7vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dx6l2l7vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:heroku-wordmark" {...props}></Icon>
