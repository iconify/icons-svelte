<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvd8j0b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tvd8j0b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cloud" {...props}></Icon>
