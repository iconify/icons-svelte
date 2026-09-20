<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpwnv1bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xpwnv1bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:coffee" {...props}></Icon>
