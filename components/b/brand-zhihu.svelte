<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eutjkybnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eutjkybnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-zhihu" {...props}></Icon>
