<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr-3xacjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rr-3xacjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-down-solid" {...props}></Icon>
