<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpmb-7exi.css';
import '../../css/b/bv_qqwbga.css';
import '../../css/a/aeiewjq8e.css';
import '../../css/a/a9i438byf.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/l/lyqbz3bix.css';
import '../../css/g/g8a0s2nql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tpmb-7exi"/><path class="bv_qqwbga"/><path class="aeiewjq8e"/><path class="a9i438byf"/><g class="jn8qy4bru"><path class="lyqbz3bix"/><path class="g8a0s2nql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rabbit" {...props}></Icon>
