<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co3ix1bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="co3ix1bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-multiple" {...props}></Icon>
