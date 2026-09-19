<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9j6r52xi.css';
import '../../css/c/c-cig4bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f9j6r52xi"/><path class="c-cig4bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-loop-left-filled" {...props}></Icon>
