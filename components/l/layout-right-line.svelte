<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqmxermtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqmxermtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-right-line" {...props}></Icon>
