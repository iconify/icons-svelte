<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2qv74buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2qv74buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reserve-filled" {...props}></Icon>
