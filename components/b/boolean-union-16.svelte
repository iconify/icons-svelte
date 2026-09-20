<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8oo2l78d.css';
import '../../css/e/ejzs483gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z8oo2l78d"/><path clip-rule="evenodd" class="ejzs483gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:boolean-union-16" {...props}></Icon>
