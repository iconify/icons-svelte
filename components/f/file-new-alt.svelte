<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu_jclhgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bu_jclhgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:file-new-alt" {...props}></Icon>
