<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea9p51llh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea9p51llh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:android" {...props}></Icon>
