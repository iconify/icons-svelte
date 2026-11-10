<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5l9-mb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p5l9-mb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-check-20-solid" {...props}></Icon>
