<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3_41eo6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="w3_41eo6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:record-keys-compact" {...props}></Icon>
