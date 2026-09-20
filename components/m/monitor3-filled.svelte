<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6fo3wqws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6fo3wqws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:monitor3-filled" {...props}></Icon>
