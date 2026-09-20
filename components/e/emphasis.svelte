<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfo_azs3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfo_azs3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:emphasis" {...props}></Icon>
