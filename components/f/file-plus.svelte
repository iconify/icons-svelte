<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0hz00p_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0hz00p_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-plus" {...props}></Icon>
