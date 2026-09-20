<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq601vtik.css';
import '../../css/o/om7fi_u-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq601vtik"/><path class="om7fi_u-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:glink" {...props}></Icon>
