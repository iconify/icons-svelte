<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_o-vlmlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j_o-vlmlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-down-to-square" {...props}></Icon>
