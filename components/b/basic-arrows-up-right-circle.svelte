<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm8-kxq0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qm8-kxq0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-up-right-circle" {...props}></Icon>
