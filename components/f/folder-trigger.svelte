<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8v7vu7pd.css';
import '../../css/i/i_73qioux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c8v7vu7pd"/><path class="i_73qioux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-trigger" {...props}></Icon>
