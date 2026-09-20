<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfyu4cbug.css';
import '../../css/o/o95idacva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dfyu4cbug"/><path class="o95idacva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-relates-to-16" {...props}></Icon>
