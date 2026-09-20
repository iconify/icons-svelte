<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd475mn6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd475mn6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-down" {...props}></Icon>
