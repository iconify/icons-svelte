<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1-e7co-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1-e7co-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-small" {...props}></Icon>
