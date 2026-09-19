<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9zji5v_l.css';
import '../../css/s/s8s9ys03v.css';
import '../../css/s/sf_in2t8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c9zji5v_l"/><path class="s8s9ys03v"/><path class="sf_in2t8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:police" {...props}></Icon>
