<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck6mx7q6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck6mx7q6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-big" {...props}></Icon>
