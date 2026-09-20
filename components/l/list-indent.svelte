<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r24wu-b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r24wu-b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:list-indent" {...props}></Icon>
