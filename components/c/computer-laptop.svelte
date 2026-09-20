<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd_9dubqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_9dubqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-laptop" {...props}></Icon>
