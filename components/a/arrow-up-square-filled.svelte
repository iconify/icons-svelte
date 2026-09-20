<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmz8-hbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmz8-hbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-square-filled" {...props}></Icon>
