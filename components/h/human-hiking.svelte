<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvw7jmbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvw7jmbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-hiking" {...props}></Icon>
