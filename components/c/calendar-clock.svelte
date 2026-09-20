<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtzkyibhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtzkyibhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:calendar-clock" {...props}></Icon>
