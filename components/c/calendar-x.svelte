<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-e8mbbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-e8mbbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-x" {...props}></Icon>
