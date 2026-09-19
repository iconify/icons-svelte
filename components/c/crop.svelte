<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jql3tpusm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="jql3tpusm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:crop" {...props}></Icon>
