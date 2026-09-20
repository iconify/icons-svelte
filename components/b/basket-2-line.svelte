<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us5twdb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us5twdb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:basket-2-line" {...props}></Icon>
