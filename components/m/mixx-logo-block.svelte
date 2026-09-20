<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq5yukqvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq5yukqvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mixx-logo-block" {...props}></Icon>
