<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8tapb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8tapb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:blur3-filled" {...props}></Icon>
