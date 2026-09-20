<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ri8rtqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ri8rtqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:baremetrics" {...props}></Icon>
