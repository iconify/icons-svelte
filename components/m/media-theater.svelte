<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7fphkwmy.css';
import '../../css/e/eytrnn8dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7fphkwmy"/><path class="eytrnn8dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-theater" {...props}></Icon>
