<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqwma-b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqwma-b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-remove-outline" {...props}></Icon>
