<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twvoxbcrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1408};
const content = `<path class="twvoxbcrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:leanpub" {...props}></Icon>
