<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wisszls_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wisszls_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:list-task" {...props}></Icon>
