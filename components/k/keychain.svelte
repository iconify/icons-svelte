<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rouqu-bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rouqu-bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:keychain" {...props}></Icon>
