<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wth82uiax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wth82uiax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coins-02" {...props}></Icon>
