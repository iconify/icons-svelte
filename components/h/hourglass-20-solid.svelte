<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9hc76b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h9hc76b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:hourglass-20-solid" {...props}></Icon>
