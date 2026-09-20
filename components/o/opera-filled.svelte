<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtoahdcsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtoahdcsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:opera-filled" {...props}></Icon>
