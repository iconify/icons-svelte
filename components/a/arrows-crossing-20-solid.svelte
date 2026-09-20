<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd70iymwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qd70iymwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing-20-solid" {...props}></Icon>
