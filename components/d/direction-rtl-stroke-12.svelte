<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl3ostbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zl3ostbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-rtl-stroke-12" {...props}></Icon>
