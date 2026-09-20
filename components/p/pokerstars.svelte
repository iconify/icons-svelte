<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnqx-61mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15.98,"height":18.229,"left":-1.663,"top":-1.663};
const content = `<path class="rnqx-61mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pokerstars" {...props}></Icon>
