<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enuv3ub3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enuv3ub3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hourglass2-filled" {...props}></Icon>
