<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9-r9rubz.css';
import '../../css/e/e451rm0tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9-r9rubz"/><path class="e451rm0tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pie-chart-alt" {...props}></Icon>
