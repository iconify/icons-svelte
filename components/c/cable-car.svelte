<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whkmt38hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whkmt38hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cable-car" {...props}></Icon>
