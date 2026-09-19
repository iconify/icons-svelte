<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv9j0ibxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hv9j0ibxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-n" {...props}></Icon>
