<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn56m8vwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn56m8vwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-circle-filled" {...props}></Icon>
