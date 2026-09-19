<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cujn-cbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cujn-cbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:repo-forked" {...props}></Icon>
