<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1kah977l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e1kah977l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-charging-20-solid" {...props}></Icon>
