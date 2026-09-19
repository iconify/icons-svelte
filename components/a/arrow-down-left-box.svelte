<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqhott-nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kqhott-nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-left-box" {...props}></Icon>
