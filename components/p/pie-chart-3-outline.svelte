<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyzoqq60w.css';
import '../../css/k/k5gsbk5ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyzoqq60w"/><path class="k5gsbk5ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-3-outline" {...props}></Icon>
