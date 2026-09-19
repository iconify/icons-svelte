<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pecnj0bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pecnj0bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-pie-fill" {...props}></Icon>
