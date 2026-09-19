<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzdu60iel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nzdu60iel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:forward-step" {...props}></Icon>
