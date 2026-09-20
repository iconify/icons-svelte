<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsgld8g3i.css';
import '../../css/x/x1x9uub3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsgld8g3i"/><path clip-rule="evenodd" class="x1x9uub3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-alt-2-fill" {...props}></Icon>
