<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isei8jc5c.css';
import '../../css/x/x6uxd8bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isei8jc5c"/><rect class="x6uxd8bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-fill-duotone" {...props}></Icon>
