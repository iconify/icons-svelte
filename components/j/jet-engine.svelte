<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/totd4jbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="totd4jbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jet-engine" {...props}></Icon>
