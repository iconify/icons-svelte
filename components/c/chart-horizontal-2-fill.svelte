<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hswj1gb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hswj1gb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-2-fill" {...props}></Icon>
