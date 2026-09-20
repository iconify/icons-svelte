<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1o5qtg5r.css';
import '../../css/c/c2jggvbqv.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/s1f6v5brf.css';
import '../../css/c/cvl8pkduj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k1o5qtg5r"/><path class="c2jggvbqv"/><g class="jn8qy4bru"><path class="s1f6v5brf"/><path class="cvl8pkduj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flat-shoe" {...props}></Icon>
