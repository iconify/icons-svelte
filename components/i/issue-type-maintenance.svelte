<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0khhdbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0khhdbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-maintenance" {...props}></Icon>
