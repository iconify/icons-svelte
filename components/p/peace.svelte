<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9s_ays7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e9s_ays7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:peace" {...props}></Icon>
