<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5-wbctd.css';
import '../../css/j/j9noiqajd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ch5-wbctd"/><path class="j9noiqajd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-quasar" {...props}></Icon>
