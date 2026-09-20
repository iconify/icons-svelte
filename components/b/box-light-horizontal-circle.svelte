<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8hmranmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k8hmranmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-circle" {...props}></Icon>
