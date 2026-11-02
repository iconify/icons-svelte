<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsxaeflza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsxaeflza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-add-fill" {...props}></Icon>
