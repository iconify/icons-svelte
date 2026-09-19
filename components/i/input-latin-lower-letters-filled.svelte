<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfzxfn1ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lfzxfn1ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-latin-lower-letters-filled" {...props}></Icon>
