<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7m22xeac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7m22xeac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:folder-o" {...props}></Icon>
