<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzxol0-lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzxol0-lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:horn-line" {...props}></Icon>
