<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awxo2eu1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awxo2eu1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rotation" {...props}></Icon>
