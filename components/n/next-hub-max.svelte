<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qli42hr8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qli42hr8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:next-hub-max" {...props}></Icon>
