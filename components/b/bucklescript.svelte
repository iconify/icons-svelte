<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg2nk7h4t.css';
import '../../css/p/p5j9y8bnl.css';
import '../../css/k/kkgzrnb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mg2nk7h4t"/><path class="p5j9y8bnl"/><path class="kkgzrnb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bucklescript" {...props}></Icon>
