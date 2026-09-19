<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1bw5jbyk.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1bw5jbyk"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-enrichment" {...props}></Icon>
