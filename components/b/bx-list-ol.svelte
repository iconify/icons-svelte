<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbgm7hbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbgm7hbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-list-ol" {...props}></Icon>
