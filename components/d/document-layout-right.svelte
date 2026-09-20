<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yltjfhhri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yltjfhhri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:document-layout-right" {...props}></Icon>
