<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1crshb5u.css';
import '../../css/j/jfyd0-b7p.css';
import '../../css/j/j-h21xgaa.css';
import '../../css/o/osrapabyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><g class="jfyd0-b7p"><path transform="matrix(.53379 0 0 .54472 7.231 7.141)" class="j-h21xgaa"/><path transform="matrix(.53379 0 0 .54472 7.231 7.141)" class="osrapabyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-gradle-open" {...props}></Icon>
