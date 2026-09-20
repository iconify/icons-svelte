<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkak67_rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkak67_rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-o" {...props}></Icon>
