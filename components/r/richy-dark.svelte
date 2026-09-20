<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h363pobgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h363pobgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:richy-dark" {...props}></Icon>
