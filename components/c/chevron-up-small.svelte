<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-s0iogmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="l-s0iogmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:chevron-up-small" {...props}></Icon>
