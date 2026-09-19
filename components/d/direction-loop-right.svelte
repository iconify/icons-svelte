<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioh76cbbc.css';
import '../../css/k/ksr3op_7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ioh76cbbc"/><path class="ksr3op_7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-loop-right" {...props}></Icon>
