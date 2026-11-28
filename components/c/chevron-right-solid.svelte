<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpoc-7bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpoc-7bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-solid" {...props}></Icon>
