<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4ulj1j6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="a4ulj1j6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:battery" {...props}></Icon>
