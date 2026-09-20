<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbhx-705c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbhx-705c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-question-outline" {...props}></Icon>
