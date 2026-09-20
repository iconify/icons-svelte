<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqycr2byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="kqycr2byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-circle-down-f" {...props}></Icon>
