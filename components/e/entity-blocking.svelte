<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk7rb9bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bk7rb9bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:entity-blocking" {...props}></Icon>
