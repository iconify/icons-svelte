<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a5oyvs24b.css';
import '../../css/f/fj5jfhb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a5oyvs24b"/><path class="fj5jfhb3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:news" {...props}></Icon>
