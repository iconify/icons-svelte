<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwwpu4biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qwwpu4biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:logstash-input" {...props}></Icon>
