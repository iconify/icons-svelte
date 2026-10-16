<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0c_fsbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0c_fsbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:memos-dark" {...props}></Icon>
