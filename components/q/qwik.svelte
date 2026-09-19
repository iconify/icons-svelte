<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53vmbcgz.css';
import '../../css/j/jick4kgxj.css';
import '../../css/b/bxyjj4o7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="s53vmbcgz"><path class="jick4kgxj"/><path class="bxyjj4o7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:qwik" {...props}></Icon>
