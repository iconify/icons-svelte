<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsr76kaca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lsr76kaca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:go-to-editing-session" {...props}></Icon>
