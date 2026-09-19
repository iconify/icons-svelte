<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs5tpe-zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hs5tpe-zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-drizzle-fill" {...props}></Icon>
