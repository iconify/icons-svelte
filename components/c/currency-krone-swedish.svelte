<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujxbawbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujxbawbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-krone-swedish" {...props}></Icon>
