<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q44kfrbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q44kfrbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-tick-outline" {...props}></Icon>
