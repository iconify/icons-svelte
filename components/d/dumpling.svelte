<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/wrifeenme.css';
import '../../css/l/l9tqyqlhi.css';
import '../../css/o/o_o6-2bot.css';
import '../../css/g/guk772bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow wrifeenme"/><path class="l9tqyqlhi wm-shadow"/><path class="o_o6-2bot"/><path class="guk772bhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:dumpling" {...props}></Icon>
