<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a54w-8bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a54w-8bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:android-solid" {...props}></Icon>
