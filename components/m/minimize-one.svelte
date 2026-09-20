<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tujk-ablr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tujk-ablr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minimize-one" {...props}></Icon>
