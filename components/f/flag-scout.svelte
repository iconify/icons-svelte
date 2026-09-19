<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn85yfbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="fn85yfbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:flag-scout" {...props}></Icon>
