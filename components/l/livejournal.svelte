<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqfy4jbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uqfy4jbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:livejournal" {...props}></Icon>
