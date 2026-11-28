<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tycc3pbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tycc3pbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-chart-solid" {...props}></Icon>
