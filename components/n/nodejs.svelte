<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg3v7v9he.css';
import '../../css/q/qnmhn2udd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yg3v7v9he"/><path class="qnmhn2udd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nodejs" {...props}></Icon>
