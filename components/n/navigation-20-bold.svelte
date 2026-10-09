<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpzke5o9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wpzke5o9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-20-bold" {...props}></Icon>
