<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcbu6ibrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vcbu6ibrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:file-tree" {...props}></Icon>
