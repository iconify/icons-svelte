<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqs_9zbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uqs_9zbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:resize-diagonal" {...props}></Icon>
