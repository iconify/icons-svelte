<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4qw-tb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4qw-tb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-scuba-mask" {...props}></Icon>
