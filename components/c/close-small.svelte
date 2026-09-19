<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h63z7hbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h63z7hbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:close-small" {...props}></Icon>
