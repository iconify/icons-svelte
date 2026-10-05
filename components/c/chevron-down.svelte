<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm0_39fsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm0_39fsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:chevron-down" {...props}></Icon>
