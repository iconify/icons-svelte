<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub9y_mh9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub9y_mh9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:height" {...props}></Icon>
