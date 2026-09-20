<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohx99ybum.css';
import '../../css/p/pvasu6b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ohx99ybum"/><path class="pvasu6b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ngrx-store-open" {...props}></Icon>
