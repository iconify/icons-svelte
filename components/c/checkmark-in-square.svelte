<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnj-uwb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cnj-uwb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:checkmark-in-square" {...props}></Icon>
