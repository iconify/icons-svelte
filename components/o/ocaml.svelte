<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t871fxb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t871fxb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ocaml" {...props}></Icon>
