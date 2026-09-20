<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdufj77v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omdufj77v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-double-down-left-solid" {...props}></Icon>
