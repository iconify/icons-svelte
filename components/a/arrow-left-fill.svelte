<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2o65lcwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2o65lcwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-fill" {...props}></Icon>
