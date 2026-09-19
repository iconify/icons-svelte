<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lji0e9b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lji0e9b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:folder-arrow-up" {...props}></Icon>
