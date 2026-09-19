<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vambye8bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vambye8bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-up-circle-sharp" {...props}></Icon>
