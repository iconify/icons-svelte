<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqkvw4bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqkvw4bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:element-of-filled" {...props}></Icon>
