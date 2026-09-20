<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru1pniv2i.css';
import '../../css/l/lluucabrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ru1pniv2i"/><path class="lluucabrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-dropper-1" {...props}></Icon>
