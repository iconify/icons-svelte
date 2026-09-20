<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/unfzw3b8q.css';
import '../../css/f/f9bz07hha.css';
import '../../css/r/rrv638bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="unfzw3b8q"/><rect class="f9bz07hha"/><path clip-rule="evenodd" class="rrv638bwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:battery-full" {...props}></Icon>
