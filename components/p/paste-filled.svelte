<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ig7zvej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ig7zvej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:paste-filled" {...props}></Icon>
