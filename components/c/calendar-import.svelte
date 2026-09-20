<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x06nz3bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x06nz3bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-import" {...props}></Icon>
