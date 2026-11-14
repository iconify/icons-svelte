<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_c_e_bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_c_e_bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-chemistry-02" {...props}></Icon>
