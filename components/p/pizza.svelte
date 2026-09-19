<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dm1xl7-wa.css';
import '../../css/j/jxryw3brs.css';
import '../../css/c/c2gys6bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dm1xl7-wa"/><path class="jxryw3brs"/><path class="c2gys6bci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:pizza" {...props}></Icon>
