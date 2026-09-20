<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxuvsghre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oxuvsghre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:logstash-if" {...props}></Icon>
