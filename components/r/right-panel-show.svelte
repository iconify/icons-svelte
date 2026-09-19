<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt-cjh-ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mt-cjh-ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:right-panel-show" {...props}></Icon>
