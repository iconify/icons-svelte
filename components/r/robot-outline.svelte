<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4zrqh7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qk4zrqh7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:robot-outline" {...props}></Icon>
