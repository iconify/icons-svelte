<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v__dgdqvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v__dgdqvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:folder-new" {...props}></Icon>
