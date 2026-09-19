<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cno-zqbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cno-zqbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot" {...props}></Icon>
