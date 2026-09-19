<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljn1lbc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljn1lbc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-remove-01" {...props}></Icon>
