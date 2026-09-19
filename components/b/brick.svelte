<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldgi7turt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldgi7turt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brick" {...props}></Icon>
