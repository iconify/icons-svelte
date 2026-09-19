<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6bu27d_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c6bu27d_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-up-arrow-down" {...props}></Icon>
