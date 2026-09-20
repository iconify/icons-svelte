<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiap8ebun.css';
import '../../css/o/o1kvkvbiz.css';
import '../../css/n/n2y8m9bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="o1kvkvbiz"/><path class="n2y8m9bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-phpmailer" {...props}></Icon>
