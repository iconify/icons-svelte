<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-2g7-zdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q-2g7-zdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-tree" {...props}></Icon>
