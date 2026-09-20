<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek7rwjbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ek7rwjbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:key-with-house-keychain" {...props}></Icon>
