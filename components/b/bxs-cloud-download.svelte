<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxxyx0bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxyx0bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cloud-download" {...props}></Icon>
