<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbrg86wua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cbrg86wua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark-circle-fill" {...props}></Icon>
