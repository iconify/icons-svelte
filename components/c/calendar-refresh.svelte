<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pus6_rbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pus6_rbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-refresh" {...props}></Icon>
