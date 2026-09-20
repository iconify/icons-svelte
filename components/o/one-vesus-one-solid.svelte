<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny29n5mmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ny29n5mmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-vesus-one-solid" {...props}></Icon>
