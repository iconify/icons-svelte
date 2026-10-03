<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9xhsfe6o.css';
import '../../css/h/h35hfnqor.css';
import '../../css/e/ehfvjlbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":60,"height":60};
const content = `<path class="a9xhsfe6o"/><path class="h35hfnqor"/><path class="ehfvjlbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mobilizon" {...props}></Icon>
