<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kynx-6isf.css';
import '../../css/b/bjufppbwi.css';
import '../../css/y/ylytiqbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kynx-6isf"/><path class="bjufppbwi"/><path clip-rule="evenodd" class="ylytiqbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:computer-16" {...props}></Icon>
