<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4auxig8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4auxig8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dice-five" {...props}></Icon>
