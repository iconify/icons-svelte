<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egtd8ibwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egtd8ibwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:print" {...props}></Icon>
