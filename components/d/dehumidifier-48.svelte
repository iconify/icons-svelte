<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-wxdblp.css';
import '../../css/j/jv2hyob1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="jv2hyob1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dehumidifier-48" {...props}></Icon>
