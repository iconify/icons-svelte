<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdm7i77zj.css';
import '../../css/p/p0z48hbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pdm7i77zj"/><path class="p0z48hbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gamemaker-open" {...props}></Icon>
