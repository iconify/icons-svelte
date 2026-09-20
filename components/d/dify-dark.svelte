<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edyeilhyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edyeilhyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dify-dark" {...props}></Icon>
