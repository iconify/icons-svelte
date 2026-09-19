<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcq1b5bna.css';
import '../../css/t/t5mpfkbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcq1b5bna"/><path clip-rule="evenodd" class="t5mpfkbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-off-outline" {...props}></Icon>
