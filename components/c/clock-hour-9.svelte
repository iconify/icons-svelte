<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy-20d2cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy-20d2cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-9" {...props}></Icon>
