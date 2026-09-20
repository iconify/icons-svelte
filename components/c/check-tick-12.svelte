<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moxwz9eot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="moxwz9eot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:check-tick-12" {...props}></Icon>
