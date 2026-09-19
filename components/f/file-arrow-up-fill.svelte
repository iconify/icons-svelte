<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga0lxoykk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ga0lxoykk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-arrow-up-fill" {...props}></Icon>
