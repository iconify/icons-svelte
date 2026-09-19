<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwxk65rgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uwxk65rgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:dash" {...props}></Icon>
