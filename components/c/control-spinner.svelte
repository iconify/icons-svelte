<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b50ezdbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b50ezdbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-spinner" {...props}></Icon>
