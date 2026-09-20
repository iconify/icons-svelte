<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8qgey2bj.css';
import '../../css/g/gurxminzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b8qgey2bj"/><path class="gurxminzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-javascript-open" {...props}></Icon>
