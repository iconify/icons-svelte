<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5-wbctd.css';
import '../../css/j/ja8mq8bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ch5-wbctd"/><path class="ja8mq8bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-core" {...props}></Icon>
