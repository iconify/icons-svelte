<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyy1jn0kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy1jn0kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-minus" {...props}></Icon>
