<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7tu5e_1v.css';
import '../../css/k/kesyiabml.css';
import '../../css/p/p9m0wgbmb.css';
import '../../css/b/b5rjm52mb.css';
import '../../css/f/fq4_qkb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z7tu5e_1v"/><path class="kesyiabml"/><path class="p9m0wgbmb"/><path class="b5rjm52mb"/><path class="fq4_qkb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:growing-heart" {...props}></Icon>
