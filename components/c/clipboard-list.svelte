<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laczu_kou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="laczu_kou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clipboard-list" {...props}></Icon>
