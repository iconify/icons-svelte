<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1bdn5bgd.css';
import '../../css/u/ufxyupbnl.css';
import '../../css/q/qmep5shkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="r1bdn5bgd"/><rect class="ufxyupbnl"/><rect class="qmep5shkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:menu-filled" {...props}></Icon>
