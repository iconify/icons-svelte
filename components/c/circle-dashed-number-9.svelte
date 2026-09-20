<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/homhz8bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="homhz8bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-9" {...props}></Icon>
