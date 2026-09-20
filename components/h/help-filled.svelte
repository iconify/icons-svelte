<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghftd6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghftd6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:help-filled" {...props}></Icon>
