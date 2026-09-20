<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld4yb5bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld4yb5bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-bottom" {...props}></Icon>
