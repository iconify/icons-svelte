<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhjw5tknw.css';
import '../../css/e/epb7u1jzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="epb7u1jzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-error-open" {...props}></Icon>
