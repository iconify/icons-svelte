<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfzfqtlfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cfzfqtlfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gba-solid" {...props}></Icon>
