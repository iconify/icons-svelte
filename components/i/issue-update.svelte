<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bja4wpuww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bja4wpuww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-update" {...props}></Icon>
