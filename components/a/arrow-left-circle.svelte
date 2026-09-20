<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4prvz4vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4prvz4vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-left-circle" {...props}></Icon>
