<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebd7wrd7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebd7wrd7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gmail-dark" {...props}></Icon>
