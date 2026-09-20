<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hioubx9vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hioubx9vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lotion-plus-outline" {...props}></Icon>
