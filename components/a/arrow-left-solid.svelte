<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amc22hb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amc22hb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-left-solid" {...props}></Icon>
