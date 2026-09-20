<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlh79-bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlh79-bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:hand" {...props}></Icon>
