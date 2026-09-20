<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2yd9po6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2yd9po6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:grid-one" {...props}></Icon>
