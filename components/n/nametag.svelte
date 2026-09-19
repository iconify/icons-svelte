<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl_2tsmqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nl_2tsmqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:nametag" {...props}></Icon>
