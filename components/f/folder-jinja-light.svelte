<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiap8ebun.css';
import '../../css/e/ew_gy0b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="ew_gy0b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-jinja-light" {...props}></Icon>
