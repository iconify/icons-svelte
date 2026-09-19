<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulox7yzfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulox7yzfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-0203m-24px" {...props}></Icon>
