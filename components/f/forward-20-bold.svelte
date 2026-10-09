<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao5pawu6s.css';
import '../../css/v/v-ad93beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ao5pawu6s"/><path class="v-ad93beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forward-20-bold" {...props}></Icon>
