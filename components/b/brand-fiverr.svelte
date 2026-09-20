<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3x1ygbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3x1ygbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-fiverr" {...props}></Icon>
