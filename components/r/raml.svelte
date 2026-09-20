<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf0kz77ab.css';
import '../../css/o/o1_egw1bm.css';
import '../../css/n/nuw157b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rf0kz77ab"/><rect class="o1_egw1bm"/><rect class="nuw157b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:raml" {...props}></Icon>
