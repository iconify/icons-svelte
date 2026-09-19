<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qza9p6emh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="qza9p6emh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:odnoklassniki-rect" {...props}></Icon>
