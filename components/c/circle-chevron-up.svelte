<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sysu8gbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sysu8gbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevron-up" {...props}></Icon>
