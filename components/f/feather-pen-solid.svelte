<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqs759a1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqs759a1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:feather-pen-solid" {...props}></Icon>
