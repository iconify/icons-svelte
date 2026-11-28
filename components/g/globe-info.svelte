<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsvw7m6as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsvw7m6as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:globe-info" {...props}></Icon>
