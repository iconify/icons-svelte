<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neul3sbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="neul3sbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:blogger-b" {...props}></Icon>
