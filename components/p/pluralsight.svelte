<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hktm_9eaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hktm_9eaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pluralsight" {...props}></Icon>
