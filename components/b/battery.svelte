<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6plrxovz.css';
import '../../css/o/o8euiibbt.css';
import '../../css/g/g7qf7cb_o.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/n/n-c6of2tv.css';
import '../../css/o/otqin9rdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="c6plrxovz"/><path class="o8euiibbt"/><path class="g7qf7cb_o"/><g class="jn8qy4bru"><path class="n-c6of2tv"/><path class="otqin9rdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:battery" {...props}></Icon>
