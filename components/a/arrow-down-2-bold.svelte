<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou43rhu8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou43rhu8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-down-2-bold" {...props}></Icon>
