<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5el2beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ci5el2beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nunjucks" {...props}></Icon>
