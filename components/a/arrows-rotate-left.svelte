<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ropv3trbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ropv3trbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrows-rotate-left" {...props}></Icon>
