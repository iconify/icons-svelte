<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_2b3zbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_2b3zbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:comet" {...props}></Icon>
