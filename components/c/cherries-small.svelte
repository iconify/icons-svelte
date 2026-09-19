<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyen-pbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uyen-pbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cherries-small" {...props}></Icon>
