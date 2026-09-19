<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmc-b_jyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmc-b_jyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bar-chart-alt" {...props}></Icon>
