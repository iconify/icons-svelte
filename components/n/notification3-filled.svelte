<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls470t6zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls470t6zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notification3-filled" {...props}></Icon>
