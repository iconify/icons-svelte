<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-b_-ietm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c-b_-ietm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ballerina" {...props}></Icon>
