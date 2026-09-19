<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_jo19bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_jo19bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:elastic-cloud" {...props}></Icon>
