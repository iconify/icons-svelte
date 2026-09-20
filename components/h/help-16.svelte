<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3yr46bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c3yr46bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:help-16" {...props}></Icon>
