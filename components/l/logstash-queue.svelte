<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueqpadbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ueqpadbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:logstash-queue" {...props}></Icon>
