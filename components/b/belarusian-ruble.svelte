<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-m5rn9ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-m5rn9ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:belarusian-ruble" {...props}></Icon>
