<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jte6-ybzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jte6-ybzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:logstash-wordmark" {...props}></Icon>
