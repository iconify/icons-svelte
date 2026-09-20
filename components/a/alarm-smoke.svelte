<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9ajr4bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9ajr4bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-smoke" {...props}></Icon>
