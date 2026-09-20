<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbtu1bbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tbtu1bbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:javaclass" {...props}></Icon>
