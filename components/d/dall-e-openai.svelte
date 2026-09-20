<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6l2z7b3n.css';
import '../../css/m/mx4-meb8l.css';
import '../../css/j/j4e8r8b1o.css';
import '../../css/n/njwn_tbgs.css';
import '../../css/i/i367zvbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6l2z7b3n"/><path class="mx4-meb8l"/><path class="j4e8r8b1o"/><path class="njwn_tbgs"/><path class="i367zvbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dall-e-openai" {...props}></Icon>
