<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6o6gtbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6o6gtbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:assistive-listening-systems" {...props}></Icon>
