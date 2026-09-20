<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj90isbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj90isbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bicycle" {...props}></Icon>
