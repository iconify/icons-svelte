<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6c8p4bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6c8p4bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:barometer" {...props}></Icon>
