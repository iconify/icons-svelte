<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg68irb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg68irb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pulse" {...props}></Icon>
