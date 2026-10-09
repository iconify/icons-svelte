<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng_19u0xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ng_19u0xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parallelogram-48" {...props}></Icon>
