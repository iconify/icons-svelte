<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxany_f2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxany_f2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-3-fill" {...props}></Icon>
