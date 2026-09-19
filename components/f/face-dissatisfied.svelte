<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww4fyqbuj.css';
import '../../css/b/b4hv47bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="b4hv47bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-dissatisfied" {...props}></Icon>
