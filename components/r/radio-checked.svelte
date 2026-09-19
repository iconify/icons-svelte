<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz-fc7bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mz-fc7bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:radio-checked" {...props}></Icon>
