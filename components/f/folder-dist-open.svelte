<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co4jh6x4v.css';
import '../../css/c/c3tt83vyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="co4jh6x4v"/><path class="c3tt83vyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-dist-open" {...props}></Icon>
