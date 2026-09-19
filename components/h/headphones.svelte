<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apooezbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="apooezbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:headphones" {...props}></Icon>
