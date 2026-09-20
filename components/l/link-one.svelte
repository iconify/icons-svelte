<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud7xhmbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud7xhmbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:link-one" {...props}></Icon>
