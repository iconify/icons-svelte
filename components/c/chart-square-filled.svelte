<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foac4kbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="foac4kbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart-square-filled" {...props}></Icon>
