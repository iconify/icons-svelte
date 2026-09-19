<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-gepabpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u-gepabpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-fill-12" {...props}></Icon>
