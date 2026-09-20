<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2d47fcwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d2d47fcwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-symlink" {...props}></Icon>
