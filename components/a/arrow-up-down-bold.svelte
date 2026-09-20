<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onffobady.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onffobady"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-down-bold" {...props}></Icon>
