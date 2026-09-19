<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0nj7p_xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0nj7p_xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-1" {...props}></Icon>
