<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4f6-z6ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4f6-z6ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hammer-2-line" {...props}></Icon>
