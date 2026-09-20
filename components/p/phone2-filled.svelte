<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt05jtbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt05jtbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone2-filled" {...props}></Icon>
