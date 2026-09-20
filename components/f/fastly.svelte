<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvq_dmzhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvq_dmzhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fastly" {...props}></Icon>
