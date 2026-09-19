<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsxtj6giu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsxtj6giu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bath" {...props}></Icon>
