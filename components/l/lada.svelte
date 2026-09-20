<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq2_cn6qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq2_cn6qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lada" {...props}></Icon>
