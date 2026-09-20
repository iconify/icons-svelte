<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg0rbf0zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg0rbf0zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:backup" {...props}></Icon>
